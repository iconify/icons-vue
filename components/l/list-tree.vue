<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdcdetb1t.css';
import '../../css/l/l5cepo42n.css';
import '../../css/d/d2f6tqbma.css';
import '../../css/f/fmevftbqp.css';
import '../../css/d/darpsbb4k.css';
import '../../css/p/pfbbxdb2l.css';
import '../../css/d/df0-jnzum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdcdetb1t wm-shadow"/><path class="l5cepo42n wm-k"/><path class="d2f6tqbma wm-k"/><path class="fmevftbqp wm-a"/><path class="darpsbb4k wm-a"/><path class="pfbbxdb2l wm-a"/><path class="df0-jnzum wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:list-tree" /></template>
