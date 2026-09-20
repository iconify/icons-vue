<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beb4umbqn.css';
import '../../css/o/ol2kopnbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beb4umbqn"/><path class="ol2kopnbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hammer-duotone" /></template>
