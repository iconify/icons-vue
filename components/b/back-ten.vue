<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftu5u0jmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftu5u0jmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:back-ten" /></template>
