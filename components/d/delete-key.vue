<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob1rhjbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ob1rhjbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:delete-key" /></template>
