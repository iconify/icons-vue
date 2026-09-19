<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7d-ndb_c.css';
import '../../css/n/nulljp8ek.css';
import '../../css/a/a3p68ebjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><circle class="nulljp8ek"/><circle class="a3p68ebjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ellipsis-vertical" /></template>
