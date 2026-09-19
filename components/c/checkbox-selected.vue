<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/def7nybhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="def7nybhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:checkbox-selected" /></template>
