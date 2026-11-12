<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg0ripb9u.css';
import '../../css/p/p796kerln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hg0ripb9u"/><path class="p796kerln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-eagle" /></template>
