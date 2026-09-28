<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="urgu6rdlh"/><path class="k6f3ktb_l"/><path class="kkwfy8iym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-redhat" /></template>
<style>
.k6f3ktb_l {
  fill: var(--svg-color--e00, #e00);
  d: path("M24.2 24.4c1.35 0 3.3-.28 3.3-1.89a2 2 0 0 0-.032-.366l-.797-3.49c-.183-.765-.345-1.12-1.69-1.79c-1.04-.539-3.32-1.41-4-1.41c-.636 0-.82.808-1.56.808c-.722 0-1.25-.603-1.93-.603c-.646 0-1.07.442-1.39 1.35c0 0-.905 2.55-1.02 2.93a.7.7 0 0 0-.022.205c-.01.991 3.9 4.24 9.15 4.26m3.5-1.23c.183.883.183.98.183 1.09c0 1.51-1.69 2.35-3.92 2.35c-5.04 0-9.45-2.95-9.45-4.9a2 2 0 0 1 .162-.786c-1.81.086-4.16.409-4.16 2.48c0 3.39 8.04 7.57 14.4 7.57c4.88 0 6.11-2.21 6.11-3.95c0-1.37-1.18-2.92-3.32-3.85");
}

.kkwfy8iym {
  d: path("M27.7 23.2c.183.883.183.98.183 1.09c0 1.51-1.69 2.35-3.92 2.35c-5.04 0-9.45-2.95-9.45-4.9a2 2 0 0 1 .162-.786l.399-.98a.7.7 0 0 0-.022.205c0 .991 3.91 4.24 9.15 4.24c1.35 0 3.3-.28 3.3-1.89a2 2 0 0 0-.032-.366z");
}

.urgu6rdlh {
  fill: var(--svg-color--c05353, #c05353);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
