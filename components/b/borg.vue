<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b774deb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b774deb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:borg" /></template>
