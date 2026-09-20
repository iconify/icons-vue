<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGm2OFodBJ" x1="21.531" x2="25.042" y1="22.766" y2="28.463" gradientUnits="userSpaceOnUse"><stop offset="0" class="d_r2ihbwz"/><stop offset=".047" class="z347plzzo"/><stop offset=".105" class="pvu2ezbea"/><stop offset=".17" class="qivzeobuh"/><stop offset=".244" class="v775wibhk"/><stop offset=".33" class="kbuldxblk"/><stop offset=".436" class="mpikj1nut"/><stop offset=".585" class="vywwtyfrk"/><stop offset="1" class="shnth7b9f"/></linearGradient></defs><path fill="url(#SVGm2OFodBJ)" class="i4g10ubtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-wpml" /></template>
<style>
.d_r2ihbwz {
  stop-color: var(--svg-color--33879e, #33879e);
}

.i4g10ubtm {
  d: path("M15.09 2c-4.94.013-10.912 5.74-10.845 11.788c-.011 5.97 4.739 11.236 11.868 11.552c4.047.177 5.532-1.865 7.23-1.414s1.874 1.945 1.788 3.085a2.353 2.353 0 0 1-2.5 2.338c-.988-.5-.391-3.2-1.906-3.36c-.946.1-1.368.93-1.159 1.946s1.516 1.988 3.383 2.065a2.89 2.89 0 0 0 2.987-3.006a3.284 3.284 0 0 0-2.809-3.516c-1.913-.178-4.337 2.139-7.957 1.473a10.506 10.506 0 0 1-8.724-10.69c.03-6.9 6.429-10.254 10.452-10.217s6.144 1.4 6.759 3.693s-2.031 4.616-3.223 5.973s-1.822 2.266-1.572 3.851c.251 1.663 2.162 4.1 4.166 4.087s4.919-2.255 4.716-7.7a12 12 0 0 0-4.558-9.353C21.752 3.456 20.032 1.989 15.09 2");
}

.kbuldxblk {
  stop-color: var(--svg-color--b55030, #b55030);
}

.mpikj1nut {
  stop-color: var(--svg-color--c04b26, #c04b26);
}

.pvu2ezbea {
  stop-color: var(--svg-color--726c68, #726c68);
}

.qivzeobuh {
  stop-color: var(--svg-color--8e6051, #8e6051);
}

.shnth7b9f {
  stop-color: var(--svg-color--c9471f, #c9471f);
}

.v775wibhk {
  stop-color: var(--svg-color--a4573f, #a4573f);
}

.vywwtyfrk {
  stop-color: var(--svg-color--c74821, #c74821);
}

.z347plzzo {
  stop-color: var(--svg-color--537983, #537983);
}

</style>
