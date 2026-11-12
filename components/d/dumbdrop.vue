<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbuj3kxuy.css';
import '../../css/x/xl9oz1zix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="mbuj3kxuy"/><path class="xl9oz1zix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdrop" /></template>
