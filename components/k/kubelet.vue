<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgr4lpegd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgr4lpegd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:kubelet" /></template>
