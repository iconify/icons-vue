<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m51-nib4u.css';
import '../../css/g/gp8fatbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m51-nib4u"/><circle class="gp8fatbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:diff-modified-outlined" /></template>
