<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc0uusbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc0uusbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:login" /></template>
