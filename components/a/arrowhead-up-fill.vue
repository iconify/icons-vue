<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csyah5ukg.css';
import '../../css/o/ou22v7n3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csyah5ukg"/><path class="ou22v7n3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrowhead-up-fill" /></template>
