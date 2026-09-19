<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3squ__1t.css';
import '../../css/h/h8f75q1qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer w3squ__1t"/><path class="duoicon-secondary-layer h8f75q1qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:airplay" /></template>
