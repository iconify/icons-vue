<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxmz3ienn.css';
import '../../css/w/wm9w19bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="xxmz3ienn"/><path class="wm9w19bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bumpsight-dark" /></template>
