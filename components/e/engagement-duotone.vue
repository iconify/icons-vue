<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcknhyrwe.css';
import '../../css/r/r25-6db-a.css';
import '../../css/m/m-8o9lbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcknhyrwe"/><path class="r25-6db-a"/><path class="m-8o9lbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:engagement-duotone" /></template>
