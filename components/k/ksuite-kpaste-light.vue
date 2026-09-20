<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1sqqcc6o.css';
import '../../css/i/iwwx5ob6h.css';
import '../../css/c/c3vcymbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1sqqcc6o"/><path class="iwwx5ob6h"/><path class="c3vcymbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kpaste-light" /></template>
