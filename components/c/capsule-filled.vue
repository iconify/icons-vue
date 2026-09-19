<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-alk7bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-alk7bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:capsule-filled" /></template>
