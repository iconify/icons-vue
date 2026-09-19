<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzxo1rbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzxo1rbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:lock" /></template>
