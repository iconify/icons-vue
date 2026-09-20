<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygc77k-_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygc77k-_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:brackets-curly" /></template>
