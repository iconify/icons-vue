<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hdzlj2btw"/><path class="l2fdpf-kt"/><path class="yxdgu93fu"/><path class="bmloosb5r"/><path class="w7saspadp"/><path class="e6y-ddbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-israel" /></template>
<style>
.bmloosb5r {
  fill: var(--svg-color--0038b8, #0038b8);
  d: path("M.294 7.5A4 4 0 0 0 0 9v2h36V9c0-.531-.106-1.036-.294-1.5z");
}

.e6y-ddbfz {
  fill: var(--svg-color--0038b8, #0038b8);
  d: path("M.294 28.5A4 4 0 0 1 0 27v-2h36v2c0 .531-.106 1.036-.294 1.5zm16.084-7.691L18 23.618l1.622-2.809h3.243L21.244 18l1.622-2.809h-3.243L18 12.382l-1.622 2.809h-3.243L14.756 18l-1.622 2.809zm1.622.809l-.467-.809h.934zm3.133-5.427l-.467.809l-.467-.808h.934zM20.666 19l.467.808h-.934zM18 14.382l.467.809h-.934zm-1.044 1.809h2.089L20.089 18l-1.044 1.809h-2.089L15.911 18zm-1.155 0l-.467.809l-.467-.808h.934zM15.334 19l.467.808h-.934z");
}

.hdzlj2btw {
  fill: var(--svg-color--edecec, #edecec);
  d: path("m20.666 19l-.467.809h.934zM18 21.618l.467-.809h-.934z");
}

.l2fdpf-kt {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 25h36V11H0zM.294 7.5h35.413A4 4 0 0 0 32 5H4A4 4 0 0 0 .294 7.5");
}

.w7saspadp {
  fill: var(--svg-color--eee, #eee);
  d: path("M.294 28.5h35.413A4 4 0 0 1 32 31H4a4 4 0 0 1-3.706-2.5");
}

.yxdgu93fu {
  fill: var(--svg-color--edecec, #edecec);
  d: path("M21.133 16.191h-.934l.467.809zm-5.332 0h-.934l.467.809zm3.243 3.618L20.089 18l-1.045-1.809h-2.088L15.911 18l1.045 1.809zM15.334 19l-.467.809h.934zM18 14.382l-.467.809h.934z");
}

</style>
