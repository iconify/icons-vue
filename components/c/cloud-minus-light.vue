<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_ezh736y.css';
import '../../css/y/yz98lj7hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ezh736y"/><path class="yz98lj7hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-minus-light" /></template>
