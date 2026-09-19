<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aellxybok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aellxybok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:logout" /></template>
