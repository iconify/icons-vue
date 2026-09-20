<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hqv1efbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-32-filled" /></template>
<style>
.hqv1efbrd {
  fill: currentColor;
  d: path("M13.594 8.36a11.17 11.17 0 0 1 6.817 3.23c4.245 4.245 4.378 11.045.398 15.45l-.398.418l-1.229 1.228a4.5 4.5 0 0 1-6.362-.002l-9.503-9.502a4.5 4.5 0 0 1 0-6.362l1.227-1.229a11.2 11.2 0 0 1 2.578-1.927a12.8 12.8 0 0 0-.307 3.23a9 9 0 0 0-.504.464l-1.225 1.227a2 2 0 0 0 0 2.83l9.502 9.501c.78.78 2.047.781 2.828.001l1.226-1.227a8.72 8.72 0 0 0-6.14-14.886a7.2 7.2 0 0 1 1.092-2.443m-.777-5.045a4.5 4.5 0 0 1 6.364.002l9.502 9.502a4.5 4.5 0 0 1 0 6.363l-1.225 1.226a11.2 11.2 0 0 1-2.577 1.924c.24-1.061.341-2.147.305-3.23q.26-.218.504-.461l1.225-1.226c.78-.78.78-2.048 0-2.829l-9.503-9.502a2 2 0 0 0-2.827 0l-1.227 1.224a8.72 8.72 0 0 0 6.14 14.886a7.2 7.2 0 0 1-1.09 2.443a11.17 11.17 0 0 1-6.817-3.23c-4.382-4.381-4.382-11.485 0-15.867z");
}

</style>
