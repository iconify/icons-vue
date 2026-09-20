<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be64gkbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="be64gkbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lldap-light" /></template>
