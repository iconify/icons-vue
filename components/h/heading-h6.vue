<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9dr0ncsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9dr0ncsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heading-h6" /></template>
