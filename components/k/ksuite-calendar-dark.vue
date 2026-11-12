<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snixp0b7u.css';
import '../../css/b/b-02yv13v.css';
import '../../css/n/nvr0ynxmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snixp0b7u"/><path class="b-02yv13v"/><path class="nvr0ynxmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-calendar-dark" /></template>
