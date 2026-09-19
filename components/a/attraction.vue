<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crpr9nbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crpr9nbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:attraction" /></template>
