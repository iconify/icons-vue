<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnku0e3st.css';
import '../../css/u/uc2ua4u2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gnku0e3st"/><path class="uc2ua4u2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cylinder-48" /></template>
