<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f6agiibex"/><path class="gvzax-5nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:activity-status-off" /></template>
<style>
.f6agiibex {
  d: path("M8.5 4.6v-.1q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049q.07-.022.142-.036q.073-.015.146-.022T10 3h4q.074 0 .147.007t.146.022t.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142t.022.146t.007.147V5h2q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T19.5 7v8.529M17.099 21H6.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4.5 19V8.428");
}

.gvzax-5nf {
  d: path("M8.5 4.6V3h7v4.5h-4.1m-7.9-4l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
