<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwyb6n-0h.css';
import '../../css/q/qo15eky2l.css';
import '../../css/f/fr80xwbvq.css';
import '../../css/y/yi3v55ama.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="lwyb6n-0h"/><circle class="qo15eky2l"/><circle class="fr80xwbvq"/><circle class="yi3v55ama"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:entropy-filled" /></template>
