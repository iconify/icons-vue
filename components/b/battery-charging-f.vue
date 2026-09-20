<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy62p4obt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="sy62p4obt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:battery-charging-f" /></template>
