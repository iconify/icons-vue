<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afc2go00o.css';
import '../../css/e/edmiowbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afc2go00o"/><path class="edmiowbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flux-operator-light" /></template>
