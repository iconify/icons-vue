<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sab-3jbuj.css';
import '../../css/u/ugqzsebbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sab-3jbuj"/><path class="ugqzsebbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:garage" /></template>
