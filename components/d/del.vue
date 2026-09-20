<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkah51bta.css';
import '../../css/h/h5gugn-ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mkah51bta"/><path class="h5gugn-ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:del" /></template>
