<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzpem9bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-bookmark" /></template>
<style>
.hzpem9bnm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6q0-1.139.805-1.945q.806-.805 1.945-.805H9q.149 0 .287.057t.243.163l1.781 1.78H17.5q2.75 0 2.75 2.75v2.045Q19.898 10 19.5 10h-4Q12 10 12 13.5v4.75H4.5q-2.75 0-2.75-2.75zm11.5 7.5q0-2.25 2.25-2.25h4q2.25 0 2.25 2.25v5.349q0 1.133-1.007 1.651t-1.929-.139l-.878-.628q-.436-.311-.872 0l-.878.627q-.922.658-1.929.14t-1.007-1.651zm2.25-.75q-.75 0-.75.75v5.349q0 .218.194.317q.193.1.37-.026l.878-.627q1.308-.935 2.616 0l.878.626q.177.127.37.027q.194-.099.194-.317V13.5q0-.75-.75-.75zM16 14v3.164q1.5-.79 3 0V14z");
}

</style>
