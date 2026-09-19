<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehhksp36u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehhksp36u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:genaifill" /></template>
