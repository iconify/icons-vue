<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft-5lzbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft-5lzbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-circle-off" /></template>
