<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iengj9bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lamp-off" /></template>
<style>
.iengj9bmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.822 3.879q.232-.184.512-.282T8.91 3.5h6.18q.128 0 .255.019q.127.018.25.055t.239.092t.223.125t.202.157t.178.184q.082.099.148.208q.067.11.117.228l1.269 3q.021.05.039.101q.018.05.033.102q.014.052.026.105q.011.052.02.106q.008.053.013.107q.005.053.007.107v.108q-.002.054-.007.108q-.005.053-.013.107l-.02.106q-.012.052-.027.104t-.032.103t-.039.1q-.021.05-.045.098q-.024.049-.051.095q-.027.047-.057.092t-.062.088t-.068.084t-.072.079q-.038.039-.078.075q-.04.037-.082.071t-.086.065t-.09.059q-.045.028-.093.054l-.096.048q-.049.022-.1.042q-.05.019-.101.036t-.104.029q-.052.013-.105.023t-.107.017t-.107.01t-.108.003h-2.417M12 15.9V21m-3.5 0h7M3.5 3.5l17 17");
}

</style>
