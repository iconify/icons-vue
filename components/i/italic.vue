<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3e9vo9iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3e9vo9iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:italic" /></template>
