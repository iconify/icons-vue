<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyjz57b0u.css';
import '../../css/h/h124n3njl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nyjz57b0u"/><path class="h124n3njl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dovecot" /></template>
