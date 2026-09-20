<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl0w_em6f.css';
import '../../css/q/qeuinobue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="jl0w_em6f"/><path class="qeuinobue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdo" /></template>
