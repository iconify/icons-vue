<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyc322s0u.css';
import '../../css/j/jml6rubew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyc322s0u"/><path class="jml6rubew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:django-fill" /></template>
