<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm23l6zsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm23l6zsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-superset" /></template>
