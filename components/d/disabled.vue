<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciq8kjb7u.css';
import '../../css/o/ob9cd8xhy.css';
import '../../css/a/av0rcu6kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ciq8kjb7u"/><path class="ob9cd8xhy"/><path class="av0rcu6kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:disabled" /></template>
