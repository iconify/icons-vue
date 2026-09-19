<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgzn1hbsd.css';
import '../../css/z/z8y_nwpda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgzn1hbsd"/><path class="z8y_nwpda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:cloud-controller-manager" /></template>
