<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1fanbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-4-outline" /></template>
<style>
.bg1fanbmv {
  fill: currentColor;
  d: path("M6.23 21q-.929 0-1.58-.64Q4 19.722 4 18.809V5.23q0-.93.65-1.58Q5.302 3 6.23 3h10.386v14.616H6.23q-.502 0-.866.341Q5 18.3 5 18.804t.365.85t.866.346H19V5h1v16zm2.155-4.384h7.23V4h-7.23zm-1 0V4H6.23q-.523 0-.877.365Q5 4.728 5 5.23v11.79q.27-.171.574-.288t.657-.117zM5 4v13.021z");
}

</style>
