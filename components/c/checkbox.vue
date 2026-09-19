<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6tmjvv9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6tmjvv9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:checkbox" /></template>
