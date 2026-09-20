<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2xeywb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2xeywb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hammer-alt-fill" /></template>
