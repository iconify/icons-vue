<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6up6k9ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6up6k9ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:detach" /></template>
