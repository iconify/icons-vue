<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v73ackb9u.css';
import '../../css/u/uwl1pssco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v73ackb9u"/><path class="uwl1pssco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-framework" /></template>
