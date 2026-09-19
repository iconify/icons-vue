<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxj7ol8dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxj7ol8dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:iteration" /></template>
