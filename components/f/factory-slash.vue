<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dby-twbls.css';
import '../../css/b/bg9dcj-ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dby-twbls"/><path class="bg9dcj-ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:factory-slash" /></template>
