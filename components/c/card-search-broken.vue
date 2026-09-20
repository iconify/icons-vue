<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e7djpjbfe.css';
import '../../css/k/ktpncgb0v.css';
import '../../css/a/aaakgqotp.css';
import '../../css/i/i8e2akblu.css';
import '../../css/e/ehgcfqbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e7djpjbfe"/><path class="ktpncgb0v"/><circle class="aaakgqotp"/><path class="i8e2akblu"/><path class="ehgcfqbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-search-broken" /></template>
