<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-4fpjbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-4fpjbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-filter" /></template>
