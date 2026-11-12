<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftuv1nbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftuv1nbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-cassandra-light" /></template>
