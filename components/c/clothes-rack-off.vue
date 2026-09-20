<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2o286bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2o286bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clothes-rack-off" /></template>
