<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs3i02bfn.css';
import '../../css/f/fr-2ovb-v.css';
import '../../css/c/cdqasfbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="cs3i02bfn"/><path class="fr-2ovb-v"/><circle class="cdqasfbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-event-endpoint-mgmt" /></template>
