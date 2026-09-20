<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqi-7bc4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-share-outline-rounded" /></template>
<style>
.uqi-7bc4h {
  fill: currentColor;
  d: path("M4.385 17q-1 0-1.693-.692T2 14.616V9.385q0-1 .692-1.693T4.385 7h12.944l-1.02 1H4.384q-.578 0-.981.403T3 9.385v5.23q0 .58.403.982q.403.403.982.403h6.23q.214 0 .357.143q.144.143.144.357t-.144.357t-.356.143zm.807-2.384q-.348 0-.577-.23q-.23-.23-.23-.578v-3.616q0-.348.23-.577q.23-.23.577-.23h8.714q-1.206.365-1.998 1.372t-.792 2.359v.692q0 .348-.23.578t-.578.23zm8.451.74Q13.5 15.214 13.5 15v-1.884q0-.691.463-1.153t1.153-.463h5.27l-1.74-1.746q-.14-.146-.15-.357q-.01-.21.15-.35q.146-.147.347-.144t.342.143l2.388 2.389q.243.242.243.565t-.243.566l-2.363 2.363q-.166.165-.357.165t-.357-.165q-.165-.165-.165-.363q0-.199.165-.345l1.74-1.721h-5.27q-.27 0-.443.173t-.173.443V15q0 .214-.143.357T14 15.5t-.357-.143");
}

</style>
