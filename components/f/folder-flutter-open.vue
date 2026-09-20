<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1i54d5m.css';
import '../../css/n/nb3vh0bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="da1i54d5m"/><path class="nb3vh0bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-flutter-open" /></template>
