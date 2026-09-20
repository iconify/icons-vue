<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d646p8jug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-export-rounded" /></template>
<style>
.d646p8jug {
  fill: currentColor;
  d: path("m20.5 18.208l-3.265 3.246q-.14.14-.342.133t-.347-.153q-.14-.14-.14-.334t.14-.334l3.24-3.266H17q-.213 0-.357-.143T16.5 17t.143-.357T17 16.5h3.692q.349 0 .578.23t.23.578V21q0 .214-.143.357T21 21.5t-.357-.143T20.5 21zM7.044 20q-1.032 0-1.928-.504q-.897-.504-1.42-1.38q-.523-.877-.523-1.885t.523-1.885l1.09-1.846h3.906l4.37 7.5zm-1.678-8.5l3.311-5.596q.523-.877 1.41-1.39T12 4t1.904.514t1.4 1.39l1.365 2.302l-1.934 3.294zm8.982 2.664l2.9-4.983l2 3.377q-1.344-.175-2.624.24q-1.28.416-2.276 1.366");
}

</style>
