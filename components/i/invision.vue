<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iff--jbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iff--jbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:invision" /></template>
