<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfvekc1nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvekc1nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:local" /></template>
