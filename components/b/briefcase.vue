<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u35pu4bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u35pu4bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:briefcase" /></template>
