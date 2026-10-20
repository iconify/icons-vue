<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdcnc9bhs.css';
import '../../css/x/xi2u7tbob.css';
import '../../css/p/pu499sb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18.035,"height":17.5};
const content = `<path class="rdcnc9bhs"/><path class="xi2u7tbob"/><path class="pu499sb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="k8s:cloud-controller-manager" /></template>
