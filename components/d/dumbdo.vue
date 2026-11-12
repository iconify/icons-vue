<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p208krbfh.css';
import '../../css/q/qeuinobue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="p208krbfh"/><path class="qeuinobue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdo" /></template>
