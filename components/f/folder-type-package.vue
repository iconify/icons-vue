<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uddj8ib7w"/><path class="gs3znt_1r"/><path class="i22fgnr1l"/><path class="zjz37dfky"/><path class="mytisccky"/><path class="rdt4_sbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-package" /></template>
<style>
.gs3znt_1r {
  fill: var(--svg-color--f2e6c9, #f2e6c9);
  d: path("M12.78 10.008c1.689-.016 3.381 0 5.071-.006c-.4 1.726-.786 3.456-1.184 5.183H8.952c-.244 0-.488.008-.732-.01c1.515-1.727 3.047-3.439 4.56-5.167M21.358 10h5.056c1.518 1.727 3.052 3.441 4.566 5.172c-.974.021-1.95 0-2.925.009h-5.524c-.384-1.726-.793-3.449-1.173-5.181");
}

.i22fgnr1l {
  fill: var(--svg-color--efc75e, #efc75e);
  d: path("M17.85 10h3.508c.379 1.73.788 3.453 1.174 5.181h-5.866c.399-1.723.784-3.453 1.184-5.181");
}

.mytisccky {
  fill: var(--svg-color--dbb551, #dbb551);
  d: path("M16.666 15.185h5.866c-.007 1.826.009 3.654-.007 5.48a2 2 0 0 1-.163.011H16.88a2 2 0 0 1-.208-.015c-.01-1.826-.002-3.652-.006-5.476");
}

.rdt4_sbpl {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M9.881 25.85h7.617v2.933H9.881z");
}

.uddj8ib7w {
  fill: var(--svg-color--c1a153, #c1a153);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.zjz37dfky {
  fill: var(--svg-color--e7bf55, #e7bf55);
  d: path("M8.219 15.174c.244.018.488.009.732.01h7.715q-.002 2.738.006 5.475a2 2 0 0 0 .208.015h5.482q.081-.002.163-.011c.016-1.826 0-3.654.007-5.48h5.524c.975-.005 1.951.012 2.925-.009v15.824L8.22 31q-.003-7.914-.001-15.826");
}

</style>
