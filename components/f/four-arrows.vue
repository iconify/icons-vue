<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/uj5tubcvw.css';
import '../../css/r/rivlizb9k.css';
import '../../css/q/qsirhpcjy.css';
import '../../css/o/ob_he3pam.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtRUZDbUm"><g class="aql7dnt-u"><path class="uj5tubcvw"/><path class="rivlizb9k"/><path class="qsirhpcjy"/><path class="ob_he3pam"/></g></mask></defs><path mask="url(#SVGtRUZDbUm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:four-arrows" /></template>
