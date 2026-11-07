<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlx29kd6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-fill-sharp" /></template>
<style>
.qlx29kd6n {
  fill: currentColor;
  d: path("m7.476 4.234l-.746-.747l4.827-2.384c.279-.137.607-.137.886 0L21 5.329l-8.32 4.109ZM2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-2.468-2.468L13 22.621v-7.207l-2-2v9.207l-8.443-4.169A1 1 0 0 1 2 17.556V7.066l5.239 2.587l-5.946-5.946a.999.999 0 1 1 1.414-1.414m11.466 8.638L22 7.066v10.49a1 1 0 0 1-.401.8Z");
}

</style>
