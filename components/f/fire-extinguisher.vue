<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugcmfac-c.css';
import '../../css/n/nqeft6d_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="ugcmfac-c"/><path class="nqeft6d_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:fire-extinguisher" /></template>
