<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkg9k32nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkg9k32nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fraunhofer-gesellschaft" /></template>
