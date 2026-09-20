<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bn9ma7box.css';
import '../../css/u/u6ect5bic.css';
import '../../css/w/w3051s3ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn9ma7box"/><path class="u6ect5bic"/><path class="w3051s3ye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bilibili-logo" /></template>
