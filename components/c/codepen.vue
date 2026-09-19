<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk4jbvbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk4jbvbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:codepen" /></template>
