<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jab5w2bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jab5w2bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:application-instance" /></template>
