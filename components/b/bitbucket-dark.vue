<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkpf_55pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kkpf_55pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitbucket-dark" /></template>
