<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9pl-r_4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9pl-r_4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-cassandra-light" /></template>
