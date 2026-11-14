<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysdoi6azn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ice-cube-nature" /></template>
<style>
.ysdoi6azn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.594 2.503q-1.594-.854-3.188 0L5.031 4.847q-.531.285-.904.664q.12.02.227.078L11 9.149l6.646-3.56q.107-.058.227-.078q-.373-.38-.904-.664zM3.646 6.911l6.604 3.538V18q0 .186.087.35q-.466-.103-.931-.353l-4.375-2.344q-1.781-.954-1.781-2.975V7.822q0-.603.158-1.111q.098.125.238.2m14.946-.2q-.098.125-.238.2l-6.604 3.538V18q0 .186-.087.35q.466-.103.931-.353l4.375-2.344q1.781-.954 1.781-2.975V7.822q0-.603-.158-1.111m.472 9.795Q21 18.718 21 20q0 1.036-.732 1.768T18.5 22.5Q16 22.5 16 20q0-1.282 1.936-3.494q.098-.112.232-.178q.133-.066.282-.076t.29.038q.142.047.254.146q.038.032.07.07");
}

</style>
