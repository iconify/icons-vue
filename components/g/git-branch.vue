<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/infrayb3b.css';
import '../../css/b/b2ob7rojk.css';
import '../../css/p/p3u_m9_oc.css';
import '../../css/b/b4mcopbsp.css';
import '../../css/w/wlg8mzbvw.css';
import '../../css/a/a1wbzsoix.css';
import '../../css/p/pdelepbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="infrayb3b"/><path class="b2ob7rojk"/><path class="p3u_m9_oc"/><path class="b4mcopbsp"/><path class="wlg8mzbvw"/><path class="a1wbzsoix"/><path class="pdelepbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:git-branch" /></template>
