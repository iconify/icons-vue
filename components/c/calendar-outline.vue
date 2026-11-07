<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti9suu5lc.css';
import '../../css/v/v4rt0mblj.css';
import '../../css/k/kb3qv9b3z.css';
import '../../css/m/mf9o9n5rb.css';
import '../../css/i/iwj00ck4i.css';
import '../../css/a/a57658x1e.css';
import '../../css/v/vomldszvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti9suu5lc"/><path class="v4rt0mblj"/><path class="kb3qv9b3z"/><path class="mf9o9n5rb"/><path class="iwj00ck4i"/><path class="a57658x1e"/><path clip-rule="evenodd" class="vomldszvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-outline" /></template>
