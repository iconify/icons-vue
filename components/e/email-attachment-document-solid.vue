<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un3jorbwb.css';
import '../../css/c/c3h8n4bmg.css';
import '../../css/o/oc50jw6ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="un3jorbwb"/><path class="c3h8n4bmg"/><path clip-rule="evenodd" class="oc50jw6ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:email-attachment-document-solid" /></template>
