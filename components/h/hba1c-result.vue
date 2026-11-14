<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn4ba8nhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hba1c-result" /></template>
<style>
.vn4ba8nhq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.367 4.264q-1.179-1.458-1.775-2.224q-.058-.074-.132-.132q-.058-.045-.124-.078q-.066-.034-.137-.053q-.071-.02-.145-.025t-.147.004t-.143.032t-.135.06t-.12.085t-.101.107q-.596.766-1.775 2.224Q4.25 10.921 4.25 14.5q0 3.236 2.257 5.493T12 22.25t5.493-2.257T19.75 14.5q0-3.579-5.383-10.236M9.5 10.75q2 0 2 2t-2 2t-2-2t2-2m4.677.516q.048-.057.106-.103t.123-.08t.137-.054t.145-.026t.147.002t.143.031q.071.022.135.058t.121.083t.103.106t.08.123q.034.066.054.137t.026.145t-.002.147t-.031.143t-.058.135t-.083.121l-5.5 6.5q-.097.114-.229.183q-.133.068-.282.08q-.148.013-.29-.033q-.143-.045-.256-.141q-.057-.048-.103-.106t-.08-.123q-.034-.066-.054-.137t-.026-.145t.002-.147t.031-.143q.022-.071.058-.135t.083-.121zM12.5 17.25q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
