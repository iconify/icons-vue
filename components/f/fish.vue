<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik6frwa0u.css';
import '../../css/i/idgsmsbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ik6frwa0u"/><path class="idgsmsbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fish" /></template>
