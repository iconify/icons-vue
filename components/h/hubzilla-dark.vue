<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvvm0fb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pvvm0fb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hubzilla-dark" /></template>
