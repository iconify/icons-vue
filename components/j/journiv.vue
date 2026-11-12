<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feh17ircu.css';
import '../../css/v/v6phkq3ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="feh17ircu"/><path class="v6phkq3ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:journiv" /></template>
