<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbqn-gggz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbqn-gggz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-next" /></template>
