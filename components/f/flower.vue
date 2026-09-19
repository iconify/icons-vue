<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7d-ndb_c.css';
import '../../css/h/hx4nelfav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><path class="hx4nelfav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flower" /></template>
