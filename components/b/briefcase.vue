<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k70tccb4z.css';
import '../../css/j/jhd2mpbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k70tccb4z"/><path class="jhd2mpbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:briefcase" /></template>
