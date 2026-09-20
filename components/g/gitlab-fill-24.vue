<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz-trqb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz-trqb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gitlab-fill-24" /></template>
