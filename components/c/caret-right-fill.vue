<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9n2ybc0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9n2ybc0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-right-fill" /></template>
