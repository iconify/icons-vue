<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkg07ratc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkg07ratc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcase-detailed-fill" /></template>
