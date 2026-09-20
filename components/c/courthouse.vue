<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_cyjh5hd.css';
import '../../css/v/v72zxwviq.css';
import '../../css/b/bci2onbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="v72zxwviq"/><path class="bci2onbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:courthouse" /></template>
