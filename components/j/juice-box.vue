<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v891dnglp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:juice-box" /></template>
<style>
.v891dnglp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 6.816q2.5.404 2.5 3.309v8.75q0 3.375-3.375 3.375h-5.75q-3.375 0-3.375-3.375v-8.75q0-3.375 3.375-3.375h5.125V4q0-.059.009-.117t.027-.113t.045-.109q.026-.052.061-.1q.034-.047.075-.089t.089-.076t.099-.062t.108-.046l4.5-1.5q.07-.023.143-.032t.147-.004t.145.025t.137.052t.125.079q.058.045.107.101q.048.055.085.12q.036.064.06.134q.047.141.036.29q-.01.149-.077.282q-.067.134-.18.232q-.112.097-.254.145L14.75 4.541zM11.6 10.8q-.064-.086-.15-.15q-.059-.044-.126-.076q-.066-.032-.138-.051q-.071-.018-.145-.022t-.147.007t-.143.034q-.07.025-.133.063q-.064.037-.119.087t-.099.108q-.161.215-.474.628Q7.5 14.633 7.5 16q0 3.5 3.5 3.5t3.5-3.5q0-1.367-2.426-4.572q-.313-.413-.474-.628");
}

</style>
