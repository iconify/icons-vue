<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq-z9ou8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-hydrant-outline-sharp" /></template>
<style>
.lq-z9ou8o {
  fill: currentColor;
  d: path("M5.077 21v-1H7v-3.904H4.577v-4.192H7V8H5.077V7h2.042q.356-1.73 1.71-2.866Q10.185 3 12 3t3.17 1.135T16.88 7h2.043v1H17v3.904h2.423v4.192H17V20h1.923v1zM8.16 7h7.68q-.313-1.304-1.37-2.152T12 4t-2.47.848T8.16 7M8 20h8v-4.904h2.423v-2.192H16V8H8v4.904H5.577v2.192H8zm6.148-3.851q.89-.89.89-2.148t-.89-2.149q-.889-.89-2.147-.89t-2.149.89q-.89.889-.89 2.147t.89 2.149q.889.89 2.147.89t2.149-.89m-3.595-.705q-.592-.596-.592-1.448t.596-1.442t1.447-.592t1.443.596q.592.596.592 1.447t-.596 1.443t-1.447.592t-1.443-.596M12 8");
}

</style>
