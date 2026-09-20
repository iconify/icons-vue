<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvwgg2gcm.css';
import '../../css/n/n9dovwblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bvwgg2gcm"/><path class="n9dovwblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calagopus-light" /></template>
