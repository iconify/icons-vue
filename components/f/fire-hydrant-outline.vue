<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg_q45a5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-hydrant-outline" /></template>
<style>
.yg_q45a5i {
  fill: currentColor;
  d: path("M5.077 21v-1H7v-3.904H5.577q-.402 0-.701-.299t-.299-.7v-2.193q0-.402.299-.701q.299-.3.701-.3H7V8H5.077V7h2.042q.356-1.73 1.71-2.866Q10.185 3 12 3t3.17 1.135T16.88 7h2.043v1H17v3.904h1.423q.402 0 .701.299t.299.7v2.193q0 .402-.299.701q-.299.3-.701.3H17V20h1.923v1zM8.16 7h7.68q-.313-1.304-1.37-2.152T12 4t-2.47.848T8.16 7M8 20h8v-4.904h2.423v-2.192H16V8H8v4.904H5.577v2.192H8zm6.148-3.852q.89-.89.89-2.148t-.89-2.148t-2.148-.89t-2.148.89T8.962 14t.89 2.148t2.148.89t2.148-.89m-3.595-.701q-.592-.591-.592-1.447t.592-1.447T12 11.962t1.447.591t.592 1.447t-.592 1.447q-.591.592-1.447.592t-1.447-.592M12 8");
}

</style>
