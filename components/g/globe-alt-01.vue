<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwncd7vll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwncd7vll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:globe-alt-01" /></template>
