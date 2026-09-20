<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqhts3b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cancel-presentation-outline-sharp" /></template>
<style>
.dqhts3b6v {
  fill: currentColor;
  d: path("m9.4 15.308l2.6-2.6l2.6 2.6l.708-.708l-2.6-2.6l2.6-2.6l-.708-.708l-2.6 2.6l-2.6-2.6l-.708.708l2.6 2.6l-2.6 2.6zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
