<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqosw2b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqosw2b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:list-ui-alt" /></template>
