<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ri6n3ye1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-crystal" /></template>
<style>
.ri6n3ye1z {
  fill: var(--svg-color--c8c8c8, #c8c8c8);
  d: path("M29.941 19.816L19.8 29.928c-.028.028-.085.028-.169.028L5.8 26.267c-.028 0-.084-.028-.113-.113L2 12.352a.4.4 0 0 1 .028-.169l10.14-10.111c.028-.028.084-.028.169-.028l13.83 3.718c.028 0 .084.028.113.113l3.69 13.8c.056.057.03.113-.029.141M16.393 8.832L2.817 12.493q-.042 0 0 .084l9.943 9.943c.028.028.028 0 .084 0l3.662-13.548c-.057-.14-.113-.14-.113-.14");
}

</style>
