<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgrfvbb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgrfvbb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-up-b-fill" /></template>
