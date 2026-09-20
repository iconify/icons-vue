<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kctlzdb3q.css';
import '../../css/h/habz1g55j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kctlzdb3q"/><path class="habz1g55j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:location-pin" /></template>
