<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arac17bjm.css';
import '../../css/b/bjy6rwbot.css';
import '../../css/r/rc8gboi9c.css';
import '../../css/m/mfqg_7hka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="arac17bjm"/><path class="bjy6rwbot"/><path class="rc8gboi9c"/><path class="mfqg_7hka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:iceberg" /></template>
