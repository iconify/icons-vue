<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phb0fspex.css';
import '../../css/o/okn01-ktv.css';
import '../../css/f/fipn1mb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phb0fspex"/><path class="okn01-ktv"/><path class="fipn1mb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-contacts-dark" /></template>
